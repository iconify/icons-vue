<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqhuv0_bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqhuv0_bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:distribute-horizontal-center" /></template>
