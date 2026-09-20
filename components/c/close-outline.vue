<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgbr6jg2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="mgbr6jg2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:close-outline" /></template>
