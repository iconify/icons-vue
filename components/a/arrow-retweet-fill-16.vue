<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo-rxrb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oo-rxrb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-retweet-fill-16" /></template>
