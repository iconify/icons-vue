<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7ql9-bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7ql9-bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-rds-light" /></template>
