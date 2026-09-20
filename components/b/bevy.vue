<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7wrsdb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7wrsdb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bevy" /></template>
