<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqkrn3bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rqkrn3bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:clapperboard" /></template>
