<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sib82zv6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sib82zv6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-retweet-stroke-12" /></template>
