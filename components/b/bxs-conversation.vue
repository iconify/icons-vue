<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0r_-hb1w.css';
import '../../css/u/um0weqbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0r_-hb1w"/><path class="um0weqbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-conversation" /></template>
