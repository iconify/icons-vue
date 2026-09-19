<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7fybebel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k7fybebel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bug-net" /></template>
