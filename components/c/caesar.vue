<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_baz8oie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_baz8oie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:caesar" /></template>
