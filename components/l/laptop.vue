<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf-i6ybtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="jf-i6ybtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:laptop" /></template>
