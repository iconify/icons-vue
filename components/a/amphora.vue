<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epspyabwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epspyabwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:amphora" /></template>
