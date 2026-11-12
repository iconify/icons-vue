<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuscq9bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xuscq9bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:litlyx" /></template>
