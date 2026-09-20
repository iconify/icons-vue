<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc0cf7bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc0cf7bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:doctrine" /></template>
