<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh5niglok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rh5niglok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbdo-dark" /></template>
