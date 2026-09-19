<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us-ieyb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us-ieyb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:downstairs-ground" /></template>
