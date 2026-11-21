<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3w1srb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g3w1srb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docker-2017-dark" /></template>
