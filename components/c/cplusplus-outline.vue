<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2-oqbben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n2-oqbben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cplusplus-outline" /></template>
