<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unzs43b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="unzs43b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:horizontal-toggle-button-solid" /></template>
