<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqlnota6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dqlnota6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bacterium" /></template>
