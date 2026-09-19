<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiob6verm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uiob6verm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:grid-fill" /></template>
