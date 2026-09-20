<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oer5e_6vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oer5e_6vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:data-display" /></template>
