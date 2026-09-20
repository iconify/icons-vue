<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihkf2plbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihkf2plbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filen-light" /></template>
