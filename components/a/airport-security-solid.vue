<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caia8ebox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="caia8ebox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:airport-security-solid" /></template>
