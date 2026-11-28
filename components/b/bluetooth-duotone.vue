<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufc3b8blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ufc3b8blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bluetooth-duotone" /></template>
