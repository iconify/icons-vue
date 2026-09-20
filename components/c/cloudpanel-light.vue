<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh_0mrb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wh_0mrb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudpanel-light" /></template>
