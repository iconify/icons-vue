<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk1uindtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vk1uindtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:archivebox" /></template>
