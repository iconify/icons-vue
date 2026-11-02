<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-xh4q-md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-xh4q-md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-right-down-fill" /></template>
