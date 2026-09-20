<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onlwfryuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onlwfryuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ease-in-out-control-points-filled" /></template>
