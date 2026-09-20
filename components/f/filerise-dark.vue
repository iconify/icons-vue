<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l30n8pb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l30n8pb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filerise-dark" /></template>
