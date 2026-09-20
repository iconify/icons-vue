<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjns-peoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjns-peoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:firebase-logo-solid" /></template>
