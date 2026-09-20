<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k466ambil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k466ambil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:funimation-logo-solid" /></template>
