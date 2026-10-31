<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpsumob8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hpsumob8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:check-square-20-solid" /></template>
