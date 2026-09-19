<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu74euvyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lu74euvyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:inauguration" /></template>
