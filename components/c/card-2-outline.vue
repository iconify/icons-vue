<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_59mhbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_59mhbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-2-outline" /></template>
