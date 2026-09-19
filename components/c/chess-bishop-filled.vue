<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc-_tnb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc-_tnb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess-bishop-filled" /></template>
