<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk90pdnnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk90pdnnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:heading-3" /></template>
