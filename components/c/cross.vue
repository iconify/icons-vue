<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jardiabnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jardiabnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cross" /></template>
