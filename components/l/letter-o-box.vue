<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwr8ainsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwr8ainsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-o-box" /></template>
