<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v29uo-_ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v29uo-_ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:alpine-linux-logo-solid" /></template>
