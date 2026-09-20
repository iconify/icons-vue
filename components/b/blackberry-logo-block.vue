<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmpzh7bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kmpzh7bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:blackberry-logo-block" /></template>
