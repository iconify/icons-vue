<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4ewktu2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4ewktu2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-justify-fill" /></template>
