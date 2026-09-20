<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrqj4fbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrqj4fbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-plus" /></template>
