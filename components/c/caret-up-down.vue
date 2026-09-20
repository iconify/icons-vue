<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spd8p2yvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spd8p2yvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:caret-up-down" /></template>
