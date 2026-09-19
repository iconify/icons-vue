<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6g_pnb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1025};
const content = `<path class="s6g_pnb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:compile" /></template>
