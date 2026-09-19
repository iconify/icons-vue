<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_j8j347h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_j8j347h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:card-view-tiles" /></template>
