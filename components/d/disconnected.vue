<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f63fvf6ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f63fvf6ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:disconnected" /></template>
