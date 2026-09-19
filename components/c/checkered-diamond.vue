<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv_kw0bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kv_kw0bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:checkered-diamond" /></template>
