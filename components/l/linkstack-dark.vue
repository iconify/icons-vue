<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljt8zg9xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljt8zg9xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linkstack-dark" /></template>
