<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klaz9acmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klaz9acmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:check-linear" /></template>
