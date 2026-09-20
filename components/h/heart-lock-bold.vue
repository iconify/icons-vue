<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk93pacvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sk93pacvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-lock-bold" /></template>
