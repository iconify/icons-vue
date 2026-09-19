<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd_wwvzsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qd_wwvzsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:black-sea" /></template>
