<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msv_7p0iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="msv_7p0iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:link-outline" /></template>
