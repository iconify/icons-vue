<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/capct4svl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="capct4svl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:infinity-solid" /></template>
