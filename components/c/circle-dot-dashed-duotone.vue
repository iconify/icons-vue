<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7a4tsbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q7a4tsbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-dot-dashed-duotone" /></template>
