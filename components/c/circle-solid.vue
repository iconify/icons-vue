<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlluol2aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rlluol2aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:circle-solid" /></template>
