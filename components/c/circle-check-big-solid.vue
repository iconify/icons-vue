<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldcxc-d2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldcxc-d2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-check-big-solid" /></template>
