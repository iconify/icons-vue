<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt3xprf1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qt3xprf1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-logo-solid" /></template>
