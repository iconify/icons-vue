<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzry5qg5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dzry5qg5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:graph" /></template>
