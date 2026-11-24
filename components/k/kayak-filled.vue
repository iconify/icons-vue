<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_gikvbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_gikvbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:kayak-filled" /></template>
