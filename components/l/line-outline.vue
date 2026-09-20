<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejyghx2fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ejyghx2fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:line-outline" /></template>
