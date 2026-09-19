<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hspng2bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hspng2bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-woff2" /></template>
