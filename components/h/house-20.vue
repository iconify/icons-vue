<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz30y8b3r.css';
import '../../css/f/faweyo8dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dz30y8b3r"/><path class="faweyo8dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-20" /></template>
