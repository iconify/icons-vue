<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwb03actr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwb03actr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cbs" /></template>
