<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydjka0b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydjka0b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up-right" /></template>
