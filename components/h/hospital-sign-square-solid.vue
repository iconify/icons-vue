<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f915x6bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f915x6bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hospital-sign-square-solid" /></template>
