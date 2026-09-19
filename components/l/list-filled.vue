<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7i3kf9ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7i3kf9ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:list-filled" /></template>
