<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqza15bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqza15bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:finger-print" /></template>
