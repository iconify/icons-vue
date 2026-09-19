<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6a7u-sfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6a7u-sfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:help-circle-filled" /></template>
