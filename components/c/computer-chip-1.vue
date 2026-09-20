<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa86d2bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa86d2bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:computer-chip-1" /></template>
