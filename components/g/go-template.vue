<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duddcrv6n.css';
import '../../css/k/koyzp3bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="duddcrv6n"/><path class="koyzp3bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:go-template" /></template>
