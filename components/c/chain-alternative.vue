<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2nk11buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="s2nk11buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chain-alternative" /></template>
