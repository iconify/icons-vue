<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zstxp5bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zstxp5bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-minus-solid" /></template>
