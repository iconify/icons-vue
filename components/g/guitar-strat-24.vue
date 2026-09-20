<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arry-cchs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arry-cchs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-strat-24" /></template>
