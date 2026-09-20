<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv24h6bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":284.4};
const content = `<path class="mv24h6bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:heroku" /></template>
