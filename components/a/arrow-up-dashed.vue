<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt3nkjbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt3nkjbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-up-dashed" /></template>
