<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1tr9t9ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1tr9t9ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fast-rewind-fill" /></template>
