<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlhv9ehzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlhv9ehzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dividing-line-line" /></template>
