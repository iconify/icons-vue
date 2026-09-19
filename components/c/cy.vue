<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcw1yj9nl.css';
import '../../css/o/okkvq7b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gcw1yj9nl"/><path class="okkvq7b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cy" /></template>
