<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bre_3u76o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bre_3u76o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-powerpoint-solid" /></template>
