<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjhcvpbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rjhcvpbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:companion-cube" /></template>
