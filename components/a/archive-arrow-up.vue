<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf0x6_f6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf0x6_f6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:archive-arrow-up" /></template>
