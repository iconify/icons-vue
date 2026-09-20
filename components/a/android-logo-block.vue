<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q576aobhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q576aobhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:android-logo-block" /></template>
