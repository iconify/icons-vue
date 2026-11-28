<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8k0acb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8k0acb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:american-football" /></template>
