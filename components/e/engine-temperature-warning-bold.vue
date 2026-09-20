<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxaifzbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zxaifzbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:engine-temperature-warning-bold" /></template>
