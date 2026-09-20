<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biwtgccqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="biwtgccqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glitchtip-dark" /></template>
