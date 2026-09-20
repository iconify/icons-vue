<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emblogu4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="emblogu4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-roadmap-solid" /></template>
