<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy6lcguuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy6lcguuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bug-24" /></template>
