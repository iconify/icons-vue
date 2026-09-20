<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_ov9mivk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="g_ov9mivk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-plus-minus" /></template>
