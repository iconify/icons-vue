<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc3jcqkcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bc3jcqkcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:layered-armor" /></template>
