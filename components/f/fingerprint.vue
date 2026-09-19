<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml7zczbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml7zczbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:fingerprint" /></template>
