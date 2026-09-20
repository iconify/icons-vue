<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucp5eibww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucp5eibww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lcx" /></template>
