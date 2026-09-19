<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4250zhsi.css';
import '../../css/l/l8da1zbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="f4250zhsi"/><path class="l8da1zbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-linkedin" /></template>
