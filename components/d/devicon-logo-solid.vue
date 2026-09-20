<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsrl8zu3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsrl8zu3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:devicon-logo-solid" /></template>
