<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxllcrbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="rxllcrbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:google-play" /></template>
