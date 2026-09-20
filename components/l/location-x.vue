<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjepf1bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjepf1bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-x" /></template>
