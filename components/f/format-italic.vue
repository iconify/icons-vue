<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huwhpyqvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huwhpyqvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:format-italic" /></template>
