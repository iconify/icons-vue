<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhyol_beh.css';
import '../../css/r/r3s9vk_bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uhyol_beh"/><path class="r3s9vk_bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:gleam" /></template>
