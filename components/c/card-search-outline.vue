<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngtyn8b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ngtyn8b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-search-outline" /></template>
