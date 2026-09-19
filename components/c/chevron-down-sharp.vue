<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6wy2hb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d6wy2hb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-down-sharp" /></template>
