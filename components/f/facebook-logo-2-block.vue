<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo08aslyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fo08aslyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:facebook-logo-2-block" /></template>
