<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-3k0obzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q-3k0obzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-triple-up-duotone" /></template>
