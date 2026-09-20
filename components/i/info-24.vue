<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8h3kyc4w.css';
import '../../css/u/u8acicc4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8h3kyc4w"/><path clip-rule="evenodd" class="u8acicc4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:info-24" /></template>
