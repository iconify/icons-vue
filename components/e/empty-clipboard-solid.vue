<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpye2xqgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fpye2xqgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:empty-clipboard-solid" /></template>
