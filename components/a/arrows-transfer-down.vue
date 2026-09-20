<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va7509xco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va7509xco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-transfer-down" /></template>
