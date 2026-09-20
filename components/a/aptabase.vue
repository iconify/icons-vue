<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2m1vj1ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a2m1vj1ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aptabase" /></template>
