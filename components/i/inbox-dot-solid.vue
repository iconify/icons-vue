<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igazh4bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igazh4bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:inbox-dot-solid" /></template>
