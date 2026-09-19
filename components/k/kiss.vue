<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sez7-guzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sez7-guzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:kiss" /></template>
