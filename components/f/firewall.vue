<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-t-o903f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h-t-o903f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:firewall" /></template>
