<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kij9dgb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kij9dgb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:letterboxd-dark" /></template>
