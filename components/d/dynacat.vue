<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_e7a256j.css';
import '../../css/v/vs4phpb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_e7a256j"/><path class="vs4phpb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dynacat" /></template>
