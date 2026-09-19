<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf7lwylwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mf7lwylwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:body-text" /></template>
