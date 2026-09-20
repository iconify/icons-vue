<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swth-1bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swth-1bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-s" /></template>
