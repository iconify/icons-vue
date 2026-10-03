<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dal-h2blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dal-h2blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:kazakh-tenge" /></template>
