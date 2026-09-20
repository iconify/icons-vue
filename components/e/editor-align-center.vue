<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2npvv7bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v2npvv7bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-align-center" /></template>
