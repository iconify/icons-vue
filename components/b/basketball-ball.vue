<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aizo16bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aizo16bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:basketball-ball" /></template>
