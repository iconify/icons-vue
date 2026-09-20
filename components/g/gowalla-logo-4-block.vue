<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw4mo75jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aw4mo75jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gowalla-logo-4-block" /></template>
