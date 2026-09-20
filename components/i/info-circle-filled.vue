<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2fis1ivm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2fis1ivm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:info-circle-filled" /></template>
