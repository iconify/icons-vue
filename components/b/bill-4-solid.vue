<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f87ux6bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f87ux6bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bill-4-solid" /></template>
