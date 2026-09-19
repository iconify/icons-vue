<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgk9rozzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgk9rozzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:layout" /></template>
