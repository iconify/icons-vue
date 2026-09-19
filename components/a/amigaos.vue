<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5ws42bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s5ws42bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:amigaos" /></template>
