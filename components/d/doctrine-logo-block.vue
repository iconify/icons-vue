<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3-w3f3uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3-w3f3uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:doctrine-logo-block" /></template>
