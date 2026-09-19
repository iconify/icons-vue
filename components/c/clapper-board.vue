<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv6_41bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tv6_41bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:clapper-board" /></template>
