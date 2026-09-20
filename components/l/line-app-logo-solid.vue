<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7ho8gb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q7ho8gb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:line-app-logo-solid" /></template>
