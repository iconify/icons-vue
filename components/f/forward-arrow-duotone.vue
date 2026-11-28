<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3e6fzopx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary s3e6fzopx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:forward-arrow-duotone" /></template>
