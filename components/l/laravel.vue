<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thytvacbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":264};
const content = `<path class="thytvacbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:laravel" /></template>
