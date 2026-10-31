<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eebfe6rrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eebfe6rrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:accessibility-alt-round" /></template>
