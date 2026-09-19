<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozkx9c3gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ozkx9c3gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:deviantart" /></template>
