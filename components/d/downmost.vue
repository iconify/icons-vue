<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo35-tb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fo35-tb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:downmost" /></template>
