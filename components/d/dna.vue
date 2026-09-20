<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq0tz7xql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gq0tz7xql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dna" /></template>
