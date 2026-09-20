<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkwgcubuy.css';
import '../../css/o/ostcmkorl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kkwgcubuy"/><path class="ostcmkorl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:coding-apps-websites-firewall" /></template>
