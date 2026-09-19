<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or1av_2jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or1av_2jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:home-x" /></template>
