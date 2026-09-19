<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxxt6ccfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxxt6ccfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-sultan-lightstrip" /></template>
