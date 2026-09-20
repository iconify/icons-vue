<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnb-kjcok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnb-kjcok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-h-center-filled" /></template>
