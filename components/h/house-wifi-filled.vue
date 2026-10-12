<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xth3lmbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xth3lmbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:house-wifi-filled" /></template>
