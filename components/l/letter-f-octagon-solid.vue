<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_iqll3qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_iqll3qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-f-octagon-solid" /></template>
