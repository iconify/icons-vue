<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0450eucy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0450eucy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:burger-heart" /></template>
