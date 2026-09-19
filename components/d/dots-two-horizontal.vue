<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a77l2yh7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a77l2yh7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:dots-two-horizontal" /></template>
