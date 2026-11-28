<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1xw4nrpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1xw4nrpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fox-heart" /></template>
