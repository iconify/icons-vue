<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r21kixbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r21kixbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:factor" /></template>
