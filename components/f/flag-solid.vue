<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huory3bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huory3bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flag-solid" /></template>
