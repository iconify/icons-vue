<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r554d955a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r554d955a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrows-up-from-line" /></template>
