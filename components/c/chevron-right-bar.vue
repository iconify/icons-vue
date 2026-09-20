<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv7r5pu1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pv7r5pu1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chevron-right-bar" /></template>
