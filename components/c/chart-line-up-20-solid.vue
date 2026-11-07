<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpj1jdbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dpj1jdbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chart-line-up-20-solid" /></template>
