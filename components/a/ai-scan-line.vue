<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyze-dimw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyze-dimw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-scan-line" /></template>
