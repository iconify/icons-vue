<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bun2tveba.css';
import '../../css/j/jkjtg1bfn.css';
import '../../css/v/vf4j3wl2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bun2tveba"/><path class="jkjtg1bfn"/><path class="vf4j3wl2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cash-out-bold" /></template>
