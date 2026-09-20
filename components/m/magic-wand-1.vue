<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr7fw4btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nr7fw4btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:magic-wand-1" /></template>
