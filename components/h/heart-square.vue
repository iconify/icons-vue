<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omvfj0p9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omvfj0p9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:heart-square" /></template>
