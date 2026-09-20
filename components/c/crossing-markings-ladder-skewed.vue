<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlymt9bdv.css';
import '../../css/u/ufp6rz5fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hlymt9bdv"/><path class="ufp6rz5fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:crossing-markings-ladder-skewed" /></template>
