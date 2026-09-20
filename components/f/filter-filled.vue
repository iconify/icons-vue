<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyt90w0so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyt90w0so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:filter-filled" /></template>
