<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8fejlbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="n8fejlbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:fast-food-11" /></template>
