<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8es5bcrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8es5bcrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lasso-fill" /></template>
