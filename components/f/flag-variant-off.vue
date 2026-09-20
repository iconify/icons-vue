<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyd_ku8wo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyd_ku8wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-variant-off" /></template>
