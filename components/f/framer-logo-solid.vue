<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxe83b55k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zxe83b55k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:framer-logo-solid" /></template>
