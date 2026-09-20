<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0alxjbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0alxjbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:corner-down-right" /></template>
