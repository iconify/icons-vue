<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u31kqbk_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u31kqbk_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:badoo-logo-block" /></template>
