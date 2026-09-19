<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt8n9obpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="wt8n9obpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:account-add" /></template>
