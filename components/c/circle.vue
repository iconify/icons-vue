<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7gl5qb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="r7gl5qb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:circle" /></template>
