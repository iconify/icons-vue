<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckusorbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ckusorbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:back" /></template>
