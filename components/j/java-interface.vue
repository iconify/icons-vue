<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni1vsp91j.css';
import '../../css/a/atbqptbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ni1vsp91j"/><path class="atbqptbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:java-interface" /></template>
