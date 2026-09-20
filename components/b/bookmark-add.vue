<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8ebhuqwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8ebhuqwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bookmark-add" /></template>
