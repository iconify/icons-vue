<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1tin4eus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1tin4eus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:area" /></template>
