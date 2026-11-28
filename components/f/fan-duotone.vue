<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe1ockbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qe1ockbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fan-duotone" /></template>
