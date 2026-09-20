<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcvl94bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcvl94bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-box-outline" /></template>
