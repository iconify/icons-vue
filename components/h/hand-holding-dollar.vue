<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2gla-vtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="f2gla-vtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-holding-dollar" /></template>
