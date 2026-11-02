<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex5dnbc5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex5dnbc5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:large-arrow-up-fill" /></template>
