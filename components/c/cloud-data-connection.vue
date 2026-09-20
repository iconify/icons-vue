<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxnnkwbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxnnkwbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-data-connection" /></template>
