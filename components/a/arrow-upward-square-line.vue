<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6mwgcdhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6mwgcdhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-upward-square-line" /></template>
