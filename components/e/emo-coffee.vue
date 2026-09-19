<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni-w6_bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1673,"height":1000};
const content = `<path class="ni-w6_bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-coffee" /></template>
