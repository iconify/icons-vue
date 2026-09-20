<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7hnc96sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v7hnc96sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:lastpass-logo-block" /></template>
