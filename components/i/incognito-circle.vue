<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lerqotbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lerqotbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:incognito-circle" /></template>
