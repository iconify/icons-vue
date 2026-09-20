<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdd1lsb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qdd1lsb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:kerb-raised" /></template>
