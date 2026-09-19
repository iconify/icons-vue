<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b09ql63gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b09ql63gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kusarigama" /></template>
