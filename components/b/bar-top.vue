<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i206__fjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i206__fjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bar-top" /></template>
