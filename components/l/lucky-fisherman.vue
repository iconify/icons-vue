<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw7n_3bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bw7n_3bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lucky-fisherman" /></template>
