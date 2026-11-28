<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdpi4bb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdpi4bb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bread-solid" /></template>
