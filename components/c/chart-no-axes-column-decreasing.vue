<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7ads4bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7ads4bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chart-no-axes-column-decreasing" /></template>
