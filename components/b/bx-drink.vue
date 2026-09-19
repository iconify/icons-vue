<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciwn85vpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciwn85vpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-drink" /></template>
