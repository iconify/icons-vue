<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6wn3rbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l6wn3rbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:astroluma-light" /></template>
