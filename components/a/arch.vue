<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja3el70qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja3el70qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:arch" /></template>
