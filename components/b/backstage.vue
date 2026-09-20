<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fly_frblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fly_frblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:backstage" /></template>
