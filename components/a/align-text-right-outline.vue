<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myf1a-boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="myf1a-boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-text-right-outline" /></template>
