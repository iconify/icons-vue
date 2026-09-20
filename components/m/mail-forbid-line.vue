<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avh0x4bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avh0x4bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-forbid-line" /></template>
