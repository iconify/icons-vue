<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ersnx-vyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ersnx-vyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-lock-solid" /></template>
