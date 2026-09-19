<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv11b6b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pv11b6b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hand-fist" /></template>
