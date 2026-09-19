<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mte30snjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mte30snjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:flux" /></template>
