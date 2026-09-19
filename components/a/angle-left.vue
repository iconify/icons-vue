<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-hm_y_jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="h-hm_y_jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:angle-left" /></template>
