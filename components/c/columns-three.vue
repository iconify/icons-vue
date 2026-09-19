<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1cy7yb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1cy7yb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:columns-three" /></template>
