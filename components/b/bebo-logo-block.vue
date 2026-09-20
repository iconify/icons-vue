<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhzcyvl8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhzcyvl8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bebo-logo-block" /></template>
