<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_hji6de.css';
import '../../css/s/sd8x9j4es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="sd8x9j4es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:check-square-bold-duotone" /></template>
