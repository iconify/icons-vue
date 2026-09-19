<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smmhmy9uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":740,"height":850};
const content = `<path class="smmhmy9uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:instagram" /></template>
