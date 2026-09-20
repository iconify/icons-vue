<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcpbjebll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcpbjebll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:apple-fill" /></template>
