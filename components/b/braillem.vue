<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iecvh8biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="iecvh8biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillem" /></template>
