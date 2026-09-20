<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uko8-ubwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uko8-ubwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:code-asterix" /></template>
