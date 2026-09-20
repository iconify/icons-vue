<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbfuw4bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zbfuw4bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:c-plus-language-logo-solid" /></template>
