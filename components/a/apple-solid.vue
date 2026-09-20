<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qurlib_6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qurlib_6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:apple-solid" /></template>
