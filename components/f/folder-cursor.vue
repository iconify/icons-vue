<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq78els5g.css';
import '../../css/p/pnp4hqbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sq78els5g"/><path class="pnp4hqbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-cursor" /></template>
