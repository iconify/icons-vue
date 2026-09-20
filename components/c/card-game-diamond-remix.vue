<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx1utriuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lx1utriuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:card-game-diamond-remix" /></template>
