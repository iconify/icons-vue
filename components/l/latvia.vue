<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgxr_vbkp.css';
import '../../css/e/e6hapgbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="dgxr_vbkp"/><path class="e6hapgbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:latvia" /></template>
