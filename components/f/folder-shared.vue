<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd6pou8aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="yd6pou8aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:folder-shared" /></template>
