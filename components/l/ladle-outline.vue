<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tau59db3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tau59db3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ladle-outline" /></template>
