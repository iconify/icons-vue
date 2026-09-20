<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmouqvb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bmouqvb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:galaxy-2-solid" /></template>
