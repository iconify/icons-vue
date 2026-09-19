<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnh7u9f3r.css';
import '../../css/t/t0uauacth.css';
import '../../css/j/jnh3n5bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gnh7u9f3r"/><path class="t0uauacth"/><path class="jnh3n5bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:gleam-config" /></template>
