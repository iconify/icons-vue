<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5eceub-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l5eceub-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:identica-logo-block" /></template>
