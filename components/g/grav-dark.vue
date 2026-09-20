<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jom0v3bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jom0v3bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grav-dark" /></template>
