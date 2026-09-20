<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0q2btitu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k0q2btitu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gabbr-logo-solid" /></template>
