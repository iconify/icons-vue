<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4okflb5a.css';
import '../../css/j/jardiabnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4okflb5a secondary"/><path class="jardiabnv primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cross-duo" /></template>
