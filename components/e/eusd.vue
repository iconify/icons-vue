<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e35k8uvkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e35k8uvkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:eusd" /></template>
