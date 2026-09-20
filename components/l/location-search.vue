<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyt6zqbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyt6zqbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-search" /></template>
