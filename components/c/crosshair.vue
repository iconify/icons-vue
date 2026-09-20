<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7q54lbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w7q54lbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crosshair" /></template>
