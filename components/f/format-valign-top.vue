<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/infxvtblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="infxvtblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-valign-top" /></template>
