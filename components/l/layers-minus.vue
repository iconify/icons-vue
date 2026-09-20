<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kse35jbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kse35jbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:layers-minus" /></template>
