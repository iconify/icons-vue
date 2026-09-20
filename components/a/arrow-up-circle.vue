<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il9r52klx.css';
import '../../css/r/rlm82lo4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="il9r52klx"/><path class="rlm82lo4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-up-circle" /></template>
