<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aduk-tbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aduk-tbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-move-horizontal" /></template>
