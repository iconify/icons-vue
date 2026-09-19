<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1-37of7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="n1-37of7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:caravan" /></template>
