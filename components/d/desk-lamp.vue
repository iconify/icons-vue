<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5lxhxsxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z5lxhxsxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:desk-lamp" /></template>
