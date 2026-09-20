<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlg7zhbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlg7zhbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bmc" /></template>
