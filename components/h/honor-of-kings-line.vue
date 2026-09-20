<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkjs8nqse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkjs8nqse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:honor-of-kings-line" /></template>
