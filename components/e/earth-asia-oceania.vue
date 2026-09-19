<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx5v6zsnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lx5v6zsnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:earth-asia-oceania" /></template>
