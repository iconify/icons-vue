<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6-p1fb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6-p1fb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-info" /></template>
