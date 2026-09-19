<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js7h18_wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="js7h18_wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lovers" /></template>
