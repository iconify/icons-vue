<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbi89lhbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbi89lhbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-wrap-top-bottom" /></template>
