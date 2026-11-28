<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywaekn5oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywaekn5oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:earbuds-check" /></template>
