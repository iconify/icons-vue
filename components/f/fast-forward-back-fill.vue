<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys83zjbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys83zjbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:fast-forward-back-fill" /></template>
