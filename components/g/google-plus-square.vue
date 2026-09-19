<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v68-995mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="v68-995mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:google-plus-square" /></template>
