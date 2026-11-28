<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooctjbb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooctjbb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:foldable-landscape-solid" /></template>
