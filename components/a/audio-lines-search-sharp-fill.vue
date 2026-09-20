<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2c-yb89e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2c-yb89e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:audio-lines-search-sharp-fill" /></template>
