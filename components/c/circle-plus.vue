<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbirz4byx.css';
import '../../css/c/c9buwng5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbirz4byx"/><path class="c9buwng5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-plus" /></template>
