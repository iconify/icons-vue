<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buce2abta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="buce2abta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:computer-chip-1-solid" /></template>
