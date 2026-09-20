<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxjyqn1xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dxjyqn1xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:client-interface" /></template>
