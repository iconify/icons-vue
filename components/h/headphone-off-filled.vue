<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3i6ohgyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3i6ohgyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:headphone-off-filled" /></template>
