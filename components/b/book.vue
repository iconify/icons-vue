<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdhn56ehw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hdhn56ehw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:book" /></template>
