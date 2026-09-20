<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw9uy4btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jw9uy4btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudnativepg-dark" /></template>
