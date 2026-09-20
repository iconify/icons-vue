<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2bhwcb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q2bhwcb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:listmonk-light" /></template>
