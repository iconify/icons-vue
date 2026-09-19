<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv3fz4b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dv3fz4b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dotclear" /></template>
