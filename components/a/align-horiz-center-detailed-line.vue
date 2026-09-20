<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfotv0bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfotv0bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-horiz-center-detailed-line" /></template>
