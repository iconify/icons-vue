<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmxskzbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmxskzbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-float-right" /></template>
