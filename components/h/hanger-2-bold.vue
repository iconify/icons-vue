<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw23xpb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw23xpb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hanger-2-bold" /></template>
