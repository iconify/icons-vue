<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i12ji_bzg.css';
import '../../css/v/vzih_tb-s.css';
import '../../css/r/rn06_bbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i12ji_bzg"/><path class="vzih_tb-s"/><path class="rn06_bbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-lune-open" /></template>
