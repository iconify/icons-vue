<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs8b_jbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs8b_jbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:light-dark-mode-solid" /></template>
