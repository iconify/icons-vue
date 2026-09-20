<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iajrblcup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iajrblcup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bars" /></template>
