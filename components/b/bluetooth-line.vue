<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf6lz4lbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf6lz4lbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:bluetooth-line" /></template>
