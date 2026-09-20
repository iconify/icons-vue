<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk752qipy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk752qipy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:corner-down-left" /></template>
