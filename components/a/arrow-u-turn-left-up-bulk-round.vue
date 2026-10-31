<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anh4j2bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anh4j2bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-left-up-bulk-round" /></template>
