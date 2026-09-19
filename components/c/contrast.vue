<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxonpi7xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="uxonpi7xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:contrast" /></template>
