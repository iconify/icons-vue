<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwf0dbb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mwf0dbb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:graduate-cap-stroke-20" /></template>
