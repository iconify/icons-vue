<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs66_p_pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zs66_p_pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:backward-fast" /></template>
