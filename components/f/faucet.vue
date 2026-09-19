<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k536ld22v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k536ld22v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:faucet" /></template>
