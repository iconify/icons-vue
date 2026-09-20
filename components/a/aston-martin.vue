<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0f-2ebpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0f-2ebpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aston-martin" /></template>
