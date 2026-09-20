<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh-2zhm_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh-2zhm_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-l" /></template>
