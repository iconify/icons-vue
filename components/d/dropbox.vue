<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6rrxu8ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":400};
const content = `<path class="a6rrxu8ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:dropbox" /></template>
