<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr13y7_yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yr13y7_yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:fork-and-knife" /></template>
