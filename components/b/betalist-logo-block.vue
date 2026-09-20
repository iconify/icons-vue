<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkmv4-31v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hkmv4-31v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:betalist-logo-block" /></template>
