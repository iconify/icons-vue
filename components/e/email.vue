<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weqv4ab8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="weqv4ab8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:email" /></template>
