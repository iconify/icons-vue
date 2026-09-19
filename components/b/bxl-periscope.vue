<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec55z3bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec55z3bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-periscope" /></template>
