<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn11p7b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn11p7b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-rupee-2-fill" /></template>
