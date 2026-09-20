<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayd1wfizv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayd1wfizv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lock-search" /></template>
