<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjqd8pbho.css';
import '../../css/t/tgp27vi-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zjqd8pbho"/><path class="tgp27vi-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gradient" /></template>
