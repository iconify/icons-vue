<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld4osb5km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ld4osb5km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:inline-skating" /></template>
