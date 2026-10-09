<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fclurev-p.css';
import '../../css/v/v-lkcnbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fclurev-p"/><path class="v-lkcnbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crucible-20-bold" /></template>
