<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_1rmspdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_1rmspdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-scan-outline" /></template>
