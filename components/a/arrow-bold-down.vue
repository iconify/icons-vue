<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xja2x8adm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xja2x8adm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:arrow-bold-down" /></template>
