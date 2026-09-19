<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz5t1_nzh.css';
import '../../css/e/evz6bnbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fz5t1_nzh"/><path class="evz6bnbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:creative-commons-share" /></template>
