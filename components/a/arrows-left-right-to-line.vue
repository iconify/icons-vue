<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq4o_fgkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="yq4o_fgkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-left-right-to-line" /></template>
