<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3fgq2b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s3fgq2b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-tika-binary-light" /></template>
