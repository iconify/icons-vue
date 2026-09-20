<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmy26bbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmy26bbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:layers-line" /></template>
