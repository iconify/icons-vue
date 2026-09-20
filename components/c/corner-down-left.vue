<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-gzj3bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-gzj3bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:corner-down-left" /></template>
