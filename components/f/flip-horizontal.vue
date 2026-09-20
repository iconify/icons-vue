<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxe6m81df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxe6m81df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flip-horizontal" /></template>
