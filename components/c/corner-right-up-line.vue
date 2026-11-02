<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5px82j8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5px82j8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-right-up-line" /></template>
