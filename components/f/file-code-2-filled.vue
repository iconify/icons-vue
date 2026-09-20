<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsqm2vbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsqm2vbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:file-code-2-filled" /></template>
