<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy5b588xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy5b588xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jasmine" /></template>
