<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onikkmh6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="onikkmh6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kohls" /></template>
