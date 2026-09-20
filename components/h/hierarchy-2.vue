<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9xaj9h1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9xaj9h1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hierarchy-2" /></template>
