<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4hvatbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y4hvatbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:damaged-house" /></template>
