<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj-wy4bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bj-wy4bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:forearm" /></template>
