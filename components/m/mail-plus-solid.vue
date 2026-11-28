<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9bc6dlzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9bc6dlzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-plus-solid" /></template>
