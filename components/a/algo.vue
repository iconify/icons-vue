<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbk_kljvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbk_kljvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:algo" /></template>
