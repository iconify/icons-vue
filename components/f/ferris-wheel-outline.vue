<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq_4ykvlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pq_4ykvlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ferris-wheel-outline" /></template>
