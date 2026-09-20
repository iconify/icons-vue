<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf_t54b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf_t54b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:briefcase-4-fill" /></template>
