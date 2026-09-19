<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gji41wbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gji41wbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-meta" /></template>
