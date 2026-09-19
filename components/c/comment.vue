<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivn7p0b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ivn7p0b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:comment" /></template>
