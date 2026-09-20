<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g73be5v_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g73be5v_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-over-water" /></template>
