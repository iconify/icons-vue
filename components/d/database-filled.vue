<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enk1d3she.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="enk1d3she"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:database-filled" /></template>
