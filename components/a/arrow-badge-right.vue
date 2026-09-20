<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdo_ykkcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdo_ykkcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-badge-right" /></template>
