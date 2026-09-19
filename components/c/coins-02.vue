<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb68-hbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb68-hbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:coins-02" /></template>
