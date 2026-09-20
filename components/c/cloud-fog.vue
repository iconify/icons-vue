<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awwk5gzrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awwk5gzrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-fog" /></template>
