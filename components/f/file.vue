<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_scqmy4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="n_scqmy4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:file" /></template>
