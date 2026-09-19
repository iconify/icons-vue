<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7v35776a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7v35776a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-3-square-light" /></template>
