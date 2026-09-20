<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6uk2fb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s6uk2fb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:creative-commons-solid" /></template>
