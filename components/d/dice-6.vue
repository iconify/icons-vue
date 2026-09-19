<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2rng6b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y2rng6b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:dice-6" /></template>
