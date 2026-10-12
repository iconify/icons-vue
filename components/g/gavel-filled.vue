<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3kg0ka3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3kg0ka3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gavel-filled" /></template>
