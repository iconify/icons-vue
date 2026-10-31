<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1b9j_3vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1b9j_3vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-right-large-bulk-round" /></template>
