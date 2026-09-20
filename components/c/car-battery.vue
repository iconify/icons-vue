<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj_2pgc9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lj_2pgc9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-battery" /></template>
