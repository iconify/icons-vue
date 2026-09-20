<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ell9tsicb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ell9tsicb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:guildeding-logo-block" /></template>
