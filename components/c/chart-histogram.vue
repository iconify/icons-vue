<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z16kyy6mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z16kyy6mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:chart-histogram" /></template>
