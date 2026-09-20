<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie1c_b5nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ie1c_b5nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:explore-filled" /></template>
