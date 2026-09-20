<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci88u-2xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ci88u-2xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-2-bold" /></template>
