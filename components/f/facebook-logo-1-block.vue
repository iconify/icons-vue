<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyb2vob8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dyb2vob8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:facebook-logo-1-block" /></template>
