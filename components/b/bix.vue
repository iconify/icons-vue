<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo1ogpb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qo1ogpb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bix" /></template>
