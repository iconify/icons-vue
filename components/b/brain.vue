<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xot8q8bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xot8q8bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:brain" /></template>
