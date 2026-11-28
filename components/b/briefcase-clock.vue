<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgdi6jkqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgdi6jkqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:briefcase-clock" /></template>
