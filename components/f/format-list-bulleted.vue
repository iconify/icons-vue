<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twzfg2g1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twzfg2g1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-list-bulleted" /></template>
