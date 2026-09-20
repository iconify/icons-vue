<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7hi0ksbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="l7hi0ksbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:align-text-left" /></template>
