<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmsg8fb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mmsg8fb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cube" /></template>
