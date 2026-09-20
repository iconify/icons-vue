<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5sa_rb5p.css';
import '../../css/h/hn41-unac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5sa_rb5p"/><path class="hn41-unac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:asm" /></template>
