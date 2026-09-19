<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riduzfbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":331,"height":512};
const content = `<path class="riduzfbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:finaldraft" /></template>
