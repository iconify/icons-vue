<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh2hcmbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":432};
const content = `<path class="eh2hcmbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:flash-off" /></template>
