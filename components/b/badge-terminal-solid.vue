<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-7e9hbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-7e9hbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-terminal-solid" /></template>
