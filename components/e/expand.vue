<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d464e6b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d464e6b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:expand" /></template>
