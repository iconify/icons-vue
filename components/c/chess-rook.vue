<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al1wpe50a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al1wpe50a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess-rook" /></template>
