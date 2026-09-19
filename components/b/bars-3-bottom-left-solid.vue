<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q83s8q5he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q83s8q5he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3-bottom-left-solid" /></template>
