<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3v7l-00h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3v7l-00h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:clean-broom-wipe-solid" /></template>
