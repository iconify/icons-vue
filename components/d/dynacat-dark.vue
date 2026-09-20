<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvzau1gld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cvzau1gld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dynacat-dark" /></template>
