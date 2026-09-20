<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpb9q-37p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpb9q-37p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:douban" /></template>
