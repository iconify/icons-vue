<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb42qelyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qb42qelyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:indent-decrease-stroke-12" /></template>
