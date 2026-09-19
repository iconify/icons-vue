<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh3nvab7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bh3nvab7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:leo" /></template>
