<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvl_8rp-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uvl_8rp-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:holy-oak" /></template>
