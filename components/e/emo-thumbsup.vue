<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-msuac5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1447,"height":1000};
const content = `<path class="k-msuac5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-thumbsup" /></template>
