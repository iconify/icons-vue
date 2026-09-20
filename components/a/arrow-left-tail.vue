<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk8-gndff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk8-gndff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-left-tail" /></template>
