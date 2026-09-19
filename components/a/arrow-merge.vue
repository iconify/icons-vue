<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbkscvbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":280,"height":384};
const content = `<path class="rbkscvbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:arrow-merge" /></template>
