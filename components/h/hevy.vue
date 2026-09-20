<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv51zcb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv51zcb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hevy" /></template>
