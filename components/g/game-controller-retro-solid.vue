<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frs8--b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="frs8--b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:game-controller-retro-solid" /></template>
