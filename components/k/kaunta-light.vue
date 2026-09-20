<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7zj78fur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7zj78fur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kaunta-light" /></template>
