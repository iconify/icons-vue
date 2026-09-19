<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp-937wkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="bp-937wkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrows" /></template>
