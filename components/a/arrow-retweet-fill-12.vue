<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1idh6b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="k1idh6b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-retweet-fill-12" /></template>
