<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm5flfbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zm5flfbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:discordjs-wordmark" /></template>
