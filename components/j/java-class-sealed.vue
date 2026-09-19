<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/torn53bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="torn53bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:java-class-sealed" /></template>
