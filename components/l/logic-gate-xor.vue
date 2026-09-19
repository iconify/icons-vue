<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhovvmb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dhovvmb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:logic-gate-xor" /></template>
