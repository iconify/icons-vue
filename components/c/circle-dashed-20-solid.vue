<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilp_1kbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ilp_1kbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-dashed-20-solid" /></template>
