<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbml2vxhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gbml2vxhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:brush" /></template>
