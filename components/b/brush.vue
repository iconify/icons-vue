<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyf3ue2rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yyf3ue2rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:brush" /></template>
