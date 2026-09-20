<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5diqgc_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5diqgc_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-tesla" /></template>
