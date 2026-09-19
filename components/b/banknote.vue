<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebvwekb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ebvwekb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:banknote" /></template>
