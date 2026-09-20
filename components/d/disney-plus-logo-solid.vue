<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7zzlacid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v7zzlacid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:disney-plus-logo-solid" /></template>
