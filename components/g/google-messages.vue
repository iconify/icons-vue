<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifjtf2bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifjtf2bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-messages" /></template>
