<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkwl28-lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dkwl28-lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:light-sabers" /></template>
