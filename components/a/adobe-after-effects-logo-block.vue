<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpxl7f8fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zpxl7f8fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-after-effects-logo-block" /></template>
