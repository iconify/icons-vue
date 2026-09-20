<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig3ggqbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ig3ggqbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-download-add-filled" /></template>
