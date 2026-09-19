<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dunh3ea7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dunh3ea7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:caterpillar" /></template>
