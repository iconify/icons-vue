<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vom63sb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vom63sb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:horse-shelter" /></template>
