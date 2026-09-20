<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox629tbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ox629tbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:flipboard-logo-block" /></template>
