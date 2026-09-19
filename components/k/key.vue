<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqp16abjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nqp16abjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:key" /></template>
