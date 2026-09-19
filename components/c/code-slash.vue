<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpuha0xak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpuha0xak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:code-slash" /></template>
