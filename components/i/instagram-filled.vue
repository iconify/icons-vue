<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyhatftlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="oyhatftlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:instagram-filled" /></template>
