<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag0ety1ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ag0ety1ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:afterburn" /></template>
