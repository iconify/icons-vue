<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr150ojmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr150ojmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-left-right" /></template>
