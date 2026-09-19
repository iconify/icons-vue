<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uevs3izuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uevs3izuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-sleep" /></template>
