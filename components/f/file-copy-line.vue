<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9t0l1bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9t0l1bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-copy-line" /></template>
