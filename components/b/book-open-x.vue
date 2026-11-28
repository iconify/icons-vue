<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8s-9ss1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8s-9ss1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:book-open-x" /></template>
