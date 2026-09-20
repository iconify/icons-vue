<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n17o4wbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n17o4wbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docker-dark" /></template>
