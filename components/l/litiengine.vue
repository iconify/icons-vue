<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyr61nbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyr61nbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:litiengine" /></template>
