<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz7aj4fgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz7aj4fgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:grid-small" /></template>
