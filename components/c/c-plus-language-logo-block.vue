<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0vzk4-mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i0vzk4-mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:c-plus-language-logo-block" /></template>
