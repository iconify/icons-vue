<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itc5zdbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itc5zdbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-circle-outline" /></template>
