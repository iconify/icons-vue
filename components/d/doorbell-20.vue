<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp-lybbkh.css';
import '../../css/u/unvddzmln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zp-lybbkh"/><path class="unvddzmln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:doorbell-20" /></template>
