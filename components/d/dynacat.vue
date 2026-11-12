<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_e7a256j.css';
import '../../css/i/i_ae3tecy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_e7a256j"/><path class="i_ae3tecy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dynacat" /></template>
