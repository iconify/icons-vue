<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbp_y203a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qbp_y203a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:azure-devops" /></template>
