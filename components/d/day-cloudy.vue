<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izykwd8ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":24};
const content = `<path class="izykwd8ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:day-cloudy" /></template>
