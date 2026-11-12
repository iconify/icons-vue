<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jar70jbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jar70jbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glances-light" /></template>
