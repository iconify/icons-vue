<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv_hd5bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gv_hd5bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:icomoon" /></template>
