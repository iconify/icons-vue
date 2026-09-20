<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr1-xddal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dr1-xddal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrows-left" /></template>
