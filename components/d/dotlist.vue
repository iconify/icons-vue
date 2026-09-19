<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6hahgbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="x6hahgbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dotlist" /></template>
