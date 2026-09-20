<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izau9c7zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izau9c7zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:axis-bank" /></template>
