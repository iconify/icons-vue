<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-sxvv4kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-sxvv4kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-linear" /></template>
