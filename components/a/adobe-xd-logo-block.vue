<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um76j9znb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="um76j9znb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-xd-logo-block" /></template>
