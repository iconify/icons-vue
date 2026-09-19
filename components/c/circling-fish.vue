<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9p9psbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k9p9psbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:circling-fish" /></template>
