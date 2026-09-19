<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi3dao0ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bi3dao0ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:armchair" /></template>
