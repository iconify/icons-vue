<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyj0qsyvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wyj0qsyvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:location-filled" /></template>
