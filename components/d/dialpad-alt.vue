<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubwaw7-jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubwaw7-jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:dialpad-alt" /></template>
