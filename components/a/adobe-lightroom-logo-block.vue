<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcnyw0x5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcnyw0x5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-lightroom-logo-block" /></template>
