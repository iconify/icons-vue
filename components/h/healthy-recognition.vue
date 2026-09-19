<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/salz-edul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="salz-edul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:healthy-recognition" /></template>
