<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcu5g6baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcu5g6baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:backup-filled" /></template>
