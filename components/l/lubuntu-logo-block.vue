<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpkb6h12s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jpkb6h12s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:lubuntu-logo-block" /></template>
