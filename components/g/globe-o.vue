<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1ou5xb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="b1ou5xb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-o" /></template>
