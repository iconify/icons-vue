<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_gqm6zjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_gqm6zjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:earth-fill" /></template>
