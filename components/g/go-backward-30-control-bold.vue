<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9olukbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9olukbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:go-backward-30-control-bold" /></template>
