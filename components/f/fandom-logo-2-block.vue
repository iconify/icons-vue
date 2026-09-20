<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbq_a9bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbq_a9bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:fandom-logo-2-block" /></template>
