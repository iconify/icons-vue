<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asyv5fbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="asyv5fbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-undo-circle" /></template>
