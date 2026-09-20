<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqgclqbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oqgclqbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:agent-zero" /></template>
