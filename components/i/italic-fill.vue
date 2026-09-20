<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkc6rkbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkc6rkbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:italic-fill" /></template>
