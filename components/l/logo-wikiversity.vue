<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed_jr85kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ed_jr85kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wikiversity" /></template>
