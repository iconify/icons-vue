<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2qc21b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2qc21b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitlab-light" /></template>
