<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isp5cgbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="isp5cgbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flower-remix" /></template>
