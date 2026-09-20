<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3g41gkfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3g41gkfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-down" /></template>
