<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix6phcbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ix6phcbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dressing-table-solid" /></template>
