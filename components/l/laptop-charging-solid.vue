<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt639tbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zt639tbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:laptop-charging-solid" /></template>
