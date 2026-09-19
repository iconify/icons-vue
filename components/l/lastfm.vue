<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_7xpqbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="k_7xpqbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:lastfm" /></template>
