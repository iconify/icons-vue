<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_mj__btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_mj__btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-stadia-logo-block" /></template>
