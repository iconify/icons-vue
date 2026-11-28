<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odzk71pzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odzk71pzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:aperture-solid" /></template>
