<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otrl-6b3q.css';
import '../../css/o/oq8tqccjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="otrl-6b3q"/><path class="oq8tqccjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:check-mark" /></template>
