<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjal8vb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjal8vb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chart-no-axes-column-increasing" /></template>
