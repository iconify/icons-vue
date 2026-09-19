<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy8f-purm.css';
import '../../css/v/v__h0hbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dy8f-purm"/><path class="v__h0hbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ai-label" /></template>
