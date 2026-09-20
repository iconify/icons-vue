<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfbs7wbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfbs7wbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bow" /></template>
