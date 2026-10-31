<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6vw2s0ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k6vw2s0ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h4-20-solid" /></template>
