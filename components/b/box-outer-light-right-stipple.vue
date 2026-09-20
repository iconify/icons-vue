<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_nts0kjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="v_nts0kjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-right-stipple" /></template>
