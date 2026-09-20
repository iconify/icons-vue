<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3t19-9ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3t19-9ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:add-sign-bold" /></template>
