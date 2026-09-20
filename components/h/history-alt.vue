<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2n3k_blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2n3k_blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:history-alt" /></template>
