<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo7qv5bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lo7qv5bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:download-tray-solid" /></template>
