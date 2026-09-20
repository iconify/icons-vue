<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7c5ax-1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7c5ax-1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-15-line" /></template>
