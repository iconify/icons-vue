<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3sea2bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3sea2bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bbc-iplayer-logo-2-solid" /></template>
