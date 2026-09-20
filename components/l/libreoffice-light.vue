<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rduy13jkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rduy13jkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libreoffice-light" /></template>
