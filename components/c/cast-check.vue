<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4e8ohbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4e8ohbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cast-check" /></template>
