<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kerw-sino.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kerw-sino"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:angle-double-left" /></template>
