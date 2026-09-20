<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdlgprbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdlgprbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-pub-sub" /></template>
