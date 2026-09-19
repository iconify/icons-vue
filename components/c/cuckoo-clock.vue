<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfah03bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfah03bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cuckoo-clock" /></template>
