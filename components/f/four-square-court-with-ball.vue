<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma4ppccnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ma4ppccnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four-square-court-with-ball" /></template>
