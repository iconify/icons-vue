<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o10ka4bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o10ka4bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:keyboard-solid" /></template>
