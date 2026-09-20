<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xku02obww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xku02obww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:macos-osx-logo" /></template>
