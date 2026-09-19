<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b09vim-am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b09vim-am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:disc-golf-bag" /></template>
