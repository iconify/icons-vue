<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi65ewbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bi65ewbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:align-left" /></template>
