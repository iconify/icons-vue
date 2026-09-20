<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plru1qb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="plru1qb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cam-disk-6k-seg" /></template>
