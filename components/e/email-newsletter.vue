<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr9isemdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr9isemdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-newsletter" /></template>
