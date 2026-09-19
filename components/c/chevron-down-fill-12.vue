<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7c05bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sv7c05bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-down-fill-12" /></template>
