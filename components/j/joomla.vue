<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrf76ybrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yrf76ybrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:joomla" /></template>
