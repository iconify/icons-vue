<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr5jz9f4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr5jz9f4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:cloud-moon" /></template>
