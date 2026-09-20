<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcneon1wc.css';
import '../../css/f/fdawbm_9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dcneon1wc"/><path class="fdawbm_9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bath-solid" /></template>
