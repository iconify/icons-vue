<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u828rdhnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u828rdhnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:details-more" /></template>
