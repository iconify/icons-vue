<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_ob6yb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_ob6yb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fur-boot" /></template>
