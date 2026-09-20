<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysv-tqb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ysv-tqb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:archive-f" /></template>
