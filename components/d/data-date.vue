<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh3kbwobr.css';
import '../../css/q/q7cll_b2k.css';
import '../../css/c/cpbja35_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh3kbwobr"/><path clip-rule="evenodd" class="q7cll_b2k"/><path clip-rule="evenodd" class="cpbja35_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-date" /></template>
