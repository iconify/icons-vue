<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-ha4xbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-ha4xbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:grip-horizontal" /></template>
