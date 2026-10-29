<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8pm_rsuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8pm_rsuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bold" /></template>
