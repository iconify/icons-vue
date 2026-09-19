<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n52r4v0cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n52r4v0cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cog" /></template>
