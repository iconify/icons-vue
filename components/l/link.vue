<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isiz68hyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isiz68hyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:link" /></template>
