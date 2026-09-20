<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8k0e_bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8k0e_bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:border-outer" /></template>
