<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmx-vlbrm.css';
import '../../css/j/jjyg4db0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pmx-vlbrm"/><path class="jjyg4db0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cargo-ship-48-bold" /></template>
