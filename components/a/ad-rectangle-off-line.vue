<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a--_f4bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a--_f4bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-rectangle-off-line" /></template>
