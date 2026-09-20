<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w83lar4wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w83lar4wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:grill-fork" /></template>
