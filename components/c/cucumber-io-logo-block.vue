<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nknoh5bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nknoh5bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:cucumber-io-logo-block" /></template>
