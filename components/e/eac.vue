<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmmqa04df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmmqa04df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:eac" /></template>
