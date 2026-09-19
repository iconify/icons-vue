<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qofievr1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qofievr1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hammer-and-anvil" /></template>
