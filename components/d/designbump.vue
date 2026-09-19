<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0thd4b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":360,"height":488};
const content = `<path class="r0thd4b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:designbump" /></template>
