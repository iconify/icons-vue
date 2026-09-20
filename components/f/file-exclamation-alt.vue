<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp-tde7pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp-tde7pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-exclamation-alt" /></template>
