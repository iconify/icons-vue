<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8s5c1zub.css';
import '../../css/r/rlm82lo4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t8s5c1zub"/><path class="rlm82lo4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-down-circle" /></template>
