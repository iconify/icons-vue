<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzj1rbc4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzj1rbc4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lightbulb" /></template>
