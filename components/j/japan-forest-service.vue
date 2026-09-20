<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir6jv9c4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ir6jv9c4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:japan-forest-service" /></template>
