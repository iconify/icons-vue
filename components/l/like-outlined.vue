<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teped2blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teped2blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:like-outlined" /></template>
