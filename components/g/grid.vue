<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2i6f7o9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2i6f7o9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:grid" /></template>
