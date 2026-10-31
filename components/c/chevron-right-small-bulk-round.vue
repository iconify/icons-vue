<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt0zfmnsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt0zfmnsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-right-small-bulk-round" /></template>
