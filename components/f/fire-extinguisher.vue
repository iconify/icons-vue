<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg6bv3b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="gg6bv3b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:fire-extinguisher" /></template>
