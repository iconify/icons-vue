<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cezb6vb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cezb6vb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beaker-minus-outline" /></template>
