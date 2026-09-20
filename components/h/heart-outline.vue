<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf1jg77_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf1jg77_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:heart-outline" /></template>
