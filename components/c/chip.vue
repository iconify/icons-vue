<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpxx2s2wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpxx2s2wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chip" /></template>
