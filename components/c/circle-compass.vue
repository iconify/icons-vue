<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5phapbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":32};
const content = `<path class="x5phapbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:circle-compass" /></template>
