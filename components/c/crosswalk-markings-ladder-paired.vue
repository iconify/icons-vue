<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_zv6gb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z_zv6gb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crosswalk-markings-ladder-paired" /></template>
