<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjqfp0b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jjqfp0b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kan-dark" /></template>
