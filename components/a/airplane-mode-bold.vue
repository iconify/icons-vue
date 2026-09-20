<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdxt6vsyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdxt6vsyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:airplane-mode-bold" /></template>
