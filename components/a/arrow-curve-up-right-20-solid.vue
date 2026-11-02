<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep7_n76dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ep7_n76dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-up-right-20-solid" /></template>
