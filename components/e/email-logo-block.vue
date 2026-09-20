<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh3nhbj_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rh3nhbj_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:email-logo-block" /></template>
