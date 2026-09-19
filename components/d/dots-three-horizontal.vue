<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk01w1bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dk01w1bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:dots-three-horizontal" /></template>
