<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv0nxwb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dv0nxwb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:helicopter-symbol" /></template>
