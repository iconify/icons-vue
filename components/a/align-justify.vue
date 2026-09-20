<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjsf1xcyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjsf1xcyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:align-justify" /></template>
