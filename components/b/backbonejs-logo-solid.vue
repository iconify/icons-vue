<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-3cpv8jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-3cpv8jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:backbonejs-logo-solid" /></template>
