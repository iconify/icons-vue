<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i05b62b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i05b62b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:knee-pad" /></template>
