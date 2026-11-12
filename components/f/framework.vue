<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfverpb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gfverpb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:framework" /></template>
