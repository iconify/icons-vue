<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwihln0_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uwihln0_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-logo-block" /></template>
