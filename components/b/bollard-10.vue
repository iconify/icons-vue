<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1qxmdatg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="g1qxmdatg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:bollard-10" /></template>
