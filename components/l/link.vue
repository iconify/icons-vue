<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4u87obbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4u87obbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:link" /></template>
