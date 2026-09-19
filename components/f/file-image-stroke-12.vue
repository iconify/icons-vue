<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quobgb7ei.css';
import '../../css/s/s3cqxlbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="quobgb7ei"/><circle class="s3cqxlbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-image-stroke-12" /></template>
