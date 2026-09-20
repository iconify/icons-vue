<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_g92t6bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_g92t6bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-ordered-two-tone" /></template>
