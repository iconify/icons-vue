<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g90jp1bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g90jp1bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:behance-logo-solid" /></template>
