<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkm6zb_kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lkm6zb_kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:environment-o" /></template>
