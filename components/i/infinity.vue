<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9ucdabdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p9ucdabdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:infinity" /></template>
