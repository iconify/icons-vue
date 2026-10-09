<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqjn82ber.css';
import '../../css/z/z0zraxben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yqjn82ber"/><path class="z0zraxben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:edit-48-bold" /></template>
