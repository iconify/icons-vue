<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u--3evbhh.css';
import '../../css/l/lseytrb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u--3evbhh"/><path class="lseytrb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cd-playing-bold" /></template>
