<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk6mzs3do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qk6mzs3do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:elixir" /></template>
