<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq1xl-c-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq1xl-c-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badge-sd-filled" /></template>
