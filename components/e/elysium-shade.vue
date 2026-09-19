<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flbcvmbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="flbcvmbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:elysium-shade" /></template>
