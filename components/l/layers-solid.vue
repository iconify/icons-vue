<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5b2u0bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5b2u0bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-solid" /></template>
