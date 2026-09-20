<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z50ub1z2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z50ub1z2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:blender-light" /></template>
