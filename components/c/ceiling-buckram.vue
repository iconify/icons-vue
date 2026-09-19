<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a--3-lbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a--3-lbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-buckram" /></template>
