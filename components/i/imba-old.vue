<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8d_ulb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r8d_ulb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:imba-old" /></template>
