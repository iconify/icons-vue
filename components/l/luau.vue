<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd-9drfax.css';
import '../../css/j/j3pesbbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xd-9drfax"/><path class="j3pesbbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:luau" /></template>
