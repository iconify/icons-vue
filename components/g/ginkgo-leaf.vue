<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5qsmzbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c5qsmzbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ginkgo-leaf" /></template>
