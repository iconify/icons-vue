<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unsn_va9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="unsn_va9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment-video" /></template>
