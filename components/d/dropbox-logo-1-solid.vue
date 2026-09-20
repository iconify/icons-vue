<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v34kx-pat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v34kx-pat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:dropbox-logo-1-solid" /></template>
