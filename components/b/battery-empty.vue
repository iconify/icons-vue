<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqw61wbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zqw61wbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:battery-empty" /></template>
