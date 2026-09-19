<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe3j6tb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="qe3j6tb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-image-o" /></template>
