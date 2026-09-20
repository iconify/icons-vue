<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhxmexbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhxmexbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-right" /></template>
