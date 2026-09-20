<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9o9xvyop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y9o9xvyop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:glasses" /></template>
