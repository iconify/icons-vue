<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkjt2n3sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkjt2n3sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fire-hydrant-off" /></template>
