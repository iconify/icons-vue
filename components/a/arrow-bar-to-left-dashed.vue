<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcez2jbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcez2jbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bar-to-left-dashed" /></template>
