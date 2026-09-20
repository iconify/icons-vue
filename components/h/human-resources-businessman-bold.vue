<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzud-bbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzud-bbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:human-resources-businessman-bold" /></template>
