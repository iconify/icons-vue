<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb3lupxla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tb3lupxla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-light" /></template>
