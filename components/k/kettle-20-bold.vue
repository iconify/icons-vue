<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-j_9y_2k.css';
import '../../css/n/nsncu0byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w-j_9y_2k"/><path class="nsncu0byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kettle-20-bold" /></template>
