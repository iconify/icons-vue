<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3_2z0moj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="j3_2z0moj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:angle-dobule-up" /></template>
