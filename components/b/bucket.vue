<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqwls7bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zqwls7bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:bucket" /></template>
