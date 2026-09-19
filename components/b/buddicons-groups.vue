<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn5v98bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gn5v98bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:buddicons-groups" /></template>
