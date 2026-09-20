<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg0lr7rfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gg0lr7rfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:code-sandbox-logo-solid" /></template>
