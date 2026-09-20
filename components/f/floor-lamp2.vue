<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv52a4buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cv52a4buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:floor-lamp2" /></template>
