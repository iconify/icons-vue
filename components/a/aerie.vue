<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v18hzdb8f.css';
import '../../css/d/d0u33jbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="v18hzdb8f"/><path class="d0u33jbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aerie" /></template>
