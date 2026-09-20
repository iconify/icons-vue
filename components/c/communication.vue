<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk2nm29hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tk2nm29hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:communication" /></template>
