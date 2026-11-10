<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6npj_j2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6npj_j2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-flame" /></template>
