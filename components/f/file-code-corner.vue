<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmdyl_bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmdyl_bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-code-corner" /></template>
