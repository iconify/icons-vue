<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfjcb0b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfjcb0b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:download-light" /></template>
