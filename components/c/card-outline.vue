<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhua3e2df.css';
import '../../css/x/x7_z8lltl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="fhua3e2df"/><path class="x7_z8lltl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:card-outline" /></template>
