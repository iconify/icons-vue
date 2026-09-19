<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6fiy_b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6fiy_b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:feather" /></template>
