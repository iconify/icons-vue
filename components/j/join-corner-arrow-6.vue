<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc_8fq-co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gc_8fq-co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:join-corner-arrow-6" /></template>
