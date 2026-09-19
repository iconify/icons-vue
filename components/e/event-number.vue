<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7yq96yri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z7yq96yri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:event-number" /></template>
