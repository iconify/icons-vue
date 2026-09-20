<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoqkenqop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoqkenqop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:infermatic" /></template>
