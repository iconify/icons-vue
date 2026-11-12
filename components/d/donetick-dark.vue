<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jao-hnd7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jao-hnd7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:donetick-dark" /></template>
