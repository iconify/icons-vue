<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug_jkob0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ug_jkob0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:globe" /></template>
