<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl1__qb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl1__qb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chevron-right" /></template>
