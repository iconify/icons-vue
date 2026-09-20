<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewqdwvung.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ewqdwvung"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:dollar" /></template>
