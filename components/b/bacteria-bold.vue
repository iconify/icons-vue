<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbmgbybwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sbmgbybwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bacteria-bold" /></template>
