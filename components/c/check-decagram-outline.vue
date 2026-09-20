<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe4oc5buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe4oc5buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:check-decagram-outline" /></template>
