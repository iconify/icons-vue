<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7_z7-b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f7_z7-b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:embed-photo" /></template>
