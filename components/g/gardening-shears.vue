<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq11l0bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yq11l0bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gardening-shears" /></template>
