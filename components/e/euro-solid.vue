<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgwl94b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgwl94b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:euro-solid" /></template>
