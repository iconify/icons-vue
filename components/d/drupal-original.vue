<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2p-7ubes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="d2p-7ubes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:drupal-original" /></template>
