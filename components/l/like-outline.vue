<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m96_mw9qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m96_mw9qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:like-outline" /></template>
