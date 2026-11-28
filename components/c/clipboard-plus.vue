<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei3fze0ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei3fze0ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clipboard-plus" /></template>
